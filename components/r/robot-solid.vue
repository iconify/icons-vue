<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ita8ud3ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ita8ud3ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:robot-solid" /></template>
