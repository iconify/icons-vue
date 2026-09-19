<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p766x0cdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p766x0cdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:prostate-outline-24px" /></template>
