<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbpy3zb7d.css';
import '../../css/f/fepfndbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bbpy3zb7d"/><path class="fepfndbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:star-half" /></template>
