<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv65n-s5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pv65n-s5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:modernizr" /></template>
