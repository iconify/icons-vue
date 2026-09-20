<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ellu4_7li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ellu4_7li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-heart-fill" /></template>
