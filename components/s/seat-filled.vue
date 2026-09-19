<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw15_svps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hw15_svps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:seat-filled" /></template>
