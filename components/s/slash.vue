<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr5pvac0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qr5pvac0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:slash" /></template>
