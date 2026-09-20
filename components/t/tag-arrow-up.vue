<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsyd4bbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsyd4bbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-arrow-up" /></template>
