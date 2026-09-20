<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axt6h9bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axt6h9bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:speed-fill" /></template>
