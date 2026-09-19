<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyzqo1buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hyzqo1buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:uber" /></template>
