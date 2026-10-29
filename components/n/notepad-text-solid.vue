<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_8zsnb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_8zsnb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:notepad-text-solid" /></template>
