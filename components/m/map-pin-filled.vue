<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cil0dr3xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cil0dr3xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-pin-filled" /></template>
