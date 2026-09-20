<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4udb9b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n4udb9b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radar-2-fill" /></template>
