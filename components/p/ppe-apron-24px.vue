<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl-m4bbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xl-m4bbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-apron-24px" /></template>
