<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbsqk1mni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gbsqk1mni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:star-slash-fill" /></template>
