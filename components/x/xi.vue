<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l47ieobie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l47ieobie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:xi" /></template>
