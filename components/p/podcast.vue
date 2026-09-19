<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lex4kb0jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lex4kb0jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:podcast" /></template>
