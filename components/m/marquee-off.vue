<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skq90mbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skq90mbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:marquee-off" /></template>
