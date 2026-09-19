<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bntc-zdzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":529,"height":1000};
const content = `<path class="bntc-zdzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:right-dir" /></template>
