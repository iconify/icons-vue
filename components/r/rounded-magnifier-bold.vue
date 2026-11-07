<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3vimybge.css';
import '../../css/n/nhqseef_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3vimybge"/><path class="nhqseef_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-bold" /></template>
