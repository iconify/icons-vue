<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxq6f4b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="vxq6f4b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:waterfall-11" /></template>
