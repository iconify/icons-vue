<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xafgut1dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2200,"height":2200};
const content = `<path class="xafgut1dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:swr-dark" /></template>
