<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugki3qq4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ugki3qq4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stackexchange" /></template>
