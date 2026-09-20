<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehw2eab2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehw2eab2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-by-time-outline" /></template>
