<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiel8l84e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiel8l84e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:scan-outline" /></template>
