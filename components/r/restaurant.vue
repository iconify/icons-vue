<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td4qobc7z.css';
import '../../css/z/z3jcjnr1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="td4qobc7z"/><path class="z3jcjnr1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:restaurant" /></template>
