<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjz7_5-6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjz7_5-6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-right-outline" /></template>
