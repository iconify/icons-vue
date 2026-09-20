<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1qq4suqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1qq4suqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-edit" /></template>
