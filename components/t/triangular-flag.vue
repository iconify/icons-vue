<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkygdid_m.css';
import '../../css/z/z2ukw-u9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wkygdid_m"/><path class="z2ukw-u9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:triangular-flag" /></template>
