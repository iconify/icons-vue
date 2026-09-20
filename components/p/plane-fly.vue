<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz583db1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz583db1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:plane-fly" /></template>
