<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etuget6lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="etuget6lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:school-circle-xmark" /></template>
