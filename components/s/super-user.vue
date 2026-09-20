<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwzc6v6gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwzc6v6gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:super-user" /></template>
