<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aek238bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="aek238bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mars-stroke-right" /></template>
