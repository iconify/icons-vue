<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzifvdi3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":263};
const content = `<path class="xzifvdi3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unity-light" /></template>
