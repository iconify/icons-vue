<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv-1fccnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv-1fccnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rows-fill-round" /></template>
