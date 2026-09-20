<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a04an4bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a04an4bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mx-linux" /></template>
