<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icd85j45o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="icd85j45o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:paragraph" /></template>
