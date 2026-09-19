<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xufc6zb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1025};
const content = `<path class="xufc6zb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sd" /></template>
