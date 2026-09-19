<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8e93ct4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="w8e93ct4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:transgender-alt" /></template>
