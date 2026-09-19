<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbcsn98cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbcsn98cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:merge-or-split-outline" /></template>
