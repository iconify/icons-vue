<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1mh8kczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1mh8kczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:twoo" /></template>
