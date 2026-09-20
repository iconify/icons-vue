<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6a08_vpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6a08_vpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-new-square-outline" /></template>
