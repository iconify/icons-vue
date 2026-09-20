<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/entt9cb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="entt9cb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snow-fill" /></template>
