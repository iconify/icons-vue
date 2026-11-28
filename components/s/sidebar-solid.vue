<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnc4pvh2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnc4pvh2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sidebar-solid" /></template>
