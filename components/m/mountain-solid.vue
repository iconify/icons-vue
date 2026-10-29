<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcxs1-bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcxs1-bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mountain-solid" /></template>
