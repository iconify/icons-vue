<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tku8aq34k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tku8aq34k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:mendeley" /></template>
