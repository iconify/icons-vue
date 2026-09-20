<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcj7e-b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":73};
const content = `<path class="kcj7e-b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:valkey" /></template>
