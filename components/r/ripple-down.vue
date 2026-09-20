<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rof8sct4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rof8sct4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ripple-down" /></template>
