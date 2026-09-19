<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6re6y22q.css';
import '../../css/a/ak63jmbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t6re6y22q"/><path class="ak63jmbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-fill" /></template>
