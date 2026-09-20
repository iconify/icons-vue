<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuqu2b3jw.css';
import '../../css/u/uxzknvoyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="yuqu2b3jw"/><path clip-rule="evenodd" class="uxzknvoyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:targon" /></template>
