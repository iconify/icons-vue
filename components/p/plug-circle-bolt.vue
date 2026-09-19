<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf82jj3qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lf82jj3qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plug-circle-bolt" /></template>
