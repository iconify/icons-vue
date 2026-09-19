<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrez6vbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrez6vbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rectangle-group-solid" /></template>
