<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9k81o5_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9k81o5_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:paperswithcode" /></template>
