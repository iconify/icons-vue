<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hji4_vdzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hji4_vdzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-left-fill" /></template>
