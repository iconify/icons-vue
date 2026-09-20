<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlz8g7oln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlz8g7oln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:medium-m" /></template>
