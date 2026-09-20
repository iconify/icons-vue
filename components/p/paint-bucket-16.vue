<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnp67f2po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xnp67f2po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paint-bucket-16" /></template>
