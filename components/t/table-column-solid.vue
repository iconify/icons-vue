<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzuh85mgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wzuh85mgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:table-column-solid" /></template>
