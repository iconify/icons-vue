<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxjrklgki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxjrklgki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ruby-sinatra" /></template>
