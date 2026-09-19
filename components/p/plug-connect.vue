<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs5_gcbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs5_gcbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plug-connect" /></template>
