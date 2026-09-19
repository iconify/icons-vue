<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e597_zb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="e597_zb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareg" /></template>
