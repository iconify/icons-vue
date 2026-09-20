<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr00khbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr00khbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:quantconnect" /></template>
