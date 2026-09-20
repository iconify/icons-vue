<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhj1_zgpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uhj1_zgpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:transgender" /></template>
