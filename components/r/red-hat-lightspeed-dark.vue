<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuzaj4bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zuzaj4bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:red-hat-lightspeed-dark" /></template>
