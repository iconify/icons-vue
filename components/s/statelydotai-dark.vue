<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek6sb0brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":405};
const content = `<path class="ek6sb0brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:statelydotai-dark" /></template>
