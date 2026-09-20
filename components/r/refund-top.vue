<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6g7qtnxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6g7qtnxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:refund-top" /></template>
