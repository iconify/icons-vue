<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-rxtsdyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="n-rxtsdyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-buddhist-11" /></template>
