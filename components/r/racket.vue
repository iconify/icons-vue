<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suwe9-r6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suwe9-r6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:racket" /></template>
