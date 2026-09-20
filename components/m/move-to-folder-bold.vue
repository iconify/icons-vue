<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1__tkbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1__tkbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-to-folder-bold" /></template>
