<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzwg3_boa.css';
import '../../css/y/yyposl7cp.css';
import '../../css/i/ijz7pfd4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rzwg3_boa"/><path class="yyposl7cp"/><path class="ijz7pfd4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-street-light-20" /></template>
