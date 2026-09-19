<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_ci_razz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_ci_razz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-beer" /></template>
