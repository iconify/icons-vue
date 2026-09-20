<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdmi5-b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdmi5-b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:turkish-lira" /></template>
