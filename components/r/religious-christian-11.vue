<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8wmx0buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="w8wmx0buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-christian-11" /></template>
