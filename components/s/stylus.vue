<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9sf_nobs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":200};
const content = `<path class="d9sf_nobs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:stylus" /></template>
