<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eibzgdcne.css';
import '../../css/m/mhb2ho-ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="eibzgdcne"/><path class="mhb2ho-ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:right" /></template>
