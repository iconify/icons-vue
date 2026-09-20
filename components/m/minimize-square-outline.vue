<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyhblzb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lyhblzb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-outline" /></template>
