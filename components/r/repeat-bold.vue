<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htre3kb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htre3kb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-bold" /></template>
