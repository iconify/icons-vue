<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd-201okx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sd-201okx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tent-arrows-down" /></template>
