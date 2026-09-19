<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzc7i60gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzc7i60gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snow" /></template>
