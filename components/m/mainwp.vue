<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx6sfjkov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx6sfjkov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mainwp" /></template>
