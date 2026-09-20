<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhut4zpns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhut4zpns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:presentation-filled" /></template>
