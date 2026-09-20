<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-i8abfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gh-i8abfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:not" /></template>
