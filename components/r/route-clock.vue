<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okwnt7b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okwnt7b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:route-clock" /></template>
