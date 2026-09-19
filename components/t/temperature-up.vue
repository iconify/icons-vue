<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9bqp1kzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z9bqp1kzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:temperature-up" /></template>
