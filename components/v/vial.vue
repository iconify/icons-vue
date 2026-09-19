<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klz-xsb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klz-xsb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vial" /></template>
