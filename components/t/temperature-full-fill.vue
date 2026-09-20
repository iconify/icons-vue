<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t78i5hosc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t78i5hosc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-full-fill" /></template>
