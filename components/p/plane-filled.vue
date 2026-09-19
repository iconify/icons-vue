<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viun7ub0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viun7ub0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plane-filled" /></template>
