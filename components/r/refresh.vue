<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjntb4z9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":810};
const content = `<path class="gjntb4z9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:refresh" /></template>
