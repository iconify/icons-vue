<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pted-0bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pted-0bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wpbeginner" /></template>
