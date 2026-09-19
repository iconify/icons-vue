<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y19h4g-0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y19h4g-0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal-alt-2-filled" /></template>
