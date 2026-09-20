<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovp7b9bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovp7b9bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rotate-to-horizontal-fill" /></template>
