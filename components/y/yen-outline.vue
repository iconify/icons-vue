<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuijjsb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wuijjsb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:yen-outline" /></template>
