<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzxj36kwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzxj36kwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rubymine" /></template>
