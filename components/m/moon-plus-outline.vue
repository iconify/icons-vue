<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucn26kqdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucn26kqdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:moon-plus-outline" /></template>
