<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9w8e8rbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9w8e8rbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vultr" /></template>
