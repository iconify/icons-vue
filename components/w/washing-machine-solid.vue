<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz_7f5bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_7f5bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:washing-machine-solid" /></template>
