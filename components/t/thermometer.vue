<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frd3b7bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="frd3b7bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:thermometer" /></template>
