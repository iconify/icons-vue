<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unwk3lcee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unwk3lcee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:screen-light" /></template>
