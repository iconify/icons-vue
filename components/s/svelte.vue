<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_xhkgbdq.css';
import '../../css/j/j--gjob4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":308};
const content = `<path class="s_xhkgbdq"/><path class="j--gjob4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:svelte" /></template>
