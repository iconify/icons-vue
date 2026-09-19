<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knrki_leo.css';
import '../../css/z/z9sersb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="knrki_leo"/><path class="z9sersb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:upload" /></template>
