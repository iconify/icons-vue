<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unp7gib0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unp7gib0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:spectrum" /></template>
