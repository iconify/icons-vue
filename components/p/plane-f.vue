<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhx_p3bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="dhx_p3bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:plane-f" /></template>
