<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3ndrqb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="x3ndrqb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:student" /></template>
