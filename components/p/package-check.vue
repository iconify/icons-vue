<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrkj-jswk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrkj-jswk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-check" /></template>
