<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2abs1bhy.css';
import '../../css/v/v23tyc59y.css';
import '../../css/f/fhiircb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t2abs1bhy"/><circle class="v23tyc59y"/><path class="fhiircb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-identification" /></template>
