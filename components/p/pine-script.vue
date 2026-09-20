<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihajhob6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihajhob6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pine-script" /></template>
