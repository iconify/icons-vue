<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w951mibfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w951mibfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-libra" /></template>
