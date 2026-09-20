<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6het-boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6het-boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:psl" /></template>
