<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7wes_f8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j7wes_f8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:plug" /></template>
