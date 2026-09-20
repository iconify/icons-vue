<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_l8s7bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_l8s7bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-square-vert-fill" /></template>
