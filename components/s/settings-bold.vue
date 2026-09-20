<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bklevro9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bklevro9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:settings-bold" /></template>
