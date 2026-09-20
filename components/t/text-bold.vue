<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsjyq1ccj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsjyq1ccj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-bold" /></template>
