<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4k1ngbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4k1ngbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-down-fill" /></template>
