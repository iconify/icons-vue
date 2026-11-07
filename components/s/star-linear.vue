<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dchgkpb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dchgkpb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-linear" /></template>
