<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx4qvpy-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx4qvpy-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:palo-alto-software" /></template>
