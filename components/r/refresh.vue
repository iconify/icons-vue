<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8qm_ypkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8qm_ypkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:refresh" /></template>
