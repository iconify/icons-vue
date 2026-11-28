<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4tknlb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y4tknlb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:webhook-duotone" /></template>
