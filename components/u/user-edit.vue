<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_vn6unjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_vn6unjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-edit" /></template>
