<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylh5eo05u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylh5eo05u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:piaggio-group" /></template>
