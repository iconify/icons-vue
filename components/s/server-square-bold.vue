<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0udebrkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0udebrkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-square-bold" /></template>
