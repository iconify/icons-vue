<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6lwwjqxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1600};
const content = `<path class="o6lwwjqxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:star-o" /></template>
