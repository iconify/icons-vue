<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te8r3eb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te8r3eb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:weasyl" /></template>
