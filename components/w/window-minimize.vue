<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_ejzkya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="lf_ejzkya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:window-minimize" /></template>
