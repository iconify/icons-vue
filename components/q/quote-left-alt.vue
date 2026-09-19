<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf-51cbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-51cbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:quote-left-alt" /></template>
