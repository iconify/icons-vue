<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwxfhhz9b.css';
import '../../css/p/pxcxtbcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mwxfhhz9b"/><path class="pxcxtbcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:zoom-in-16" /></template>
