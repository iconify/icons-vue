<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsyhdhbom.css';
import '../../css/m/m1jkf5b-x.css';
import '../../css/u/u72v5m6oj.css';
import '../../css/u/uba14cccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rsyhdhbom"/><path class="m1jkf5b-x"/><path class="u72v5m6oj"/><path class="uba14cccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vuejs-wordmark" /></template>
