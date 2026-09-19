<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x31ta7bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x31ta7bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:multiply" /></template>
