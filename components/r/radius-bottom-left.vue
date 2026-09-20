<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfx6rsbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfx6rsbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:radius-bottom-left" /></template>
