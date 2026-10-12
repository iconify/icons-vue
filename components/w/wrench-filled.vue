<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eak51fbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eak51fbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wrench-filled" /></template>
