<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpl68-y4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpl68-y4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-2-bold" /></template>
