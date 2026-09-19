<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0fo7-bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0fo7-bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:wifi" /></template>
