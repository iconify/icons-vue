<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueu8080la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ueu8080la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-cells-merge-outline" /></template>
