<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa1eiqb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wa1eiqb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:walk2" /></template>
