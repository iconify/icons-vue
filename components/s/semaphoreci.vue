<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2zrd1-ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g2zrd1-ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:semaphoreci" /></template>
