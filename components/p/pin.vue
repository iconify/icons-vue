<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyt7w2bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tyt7w2bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pin" /></template>
