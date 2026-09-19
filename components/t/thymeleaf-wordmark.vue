<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-zpbcpt.css';
import '../../css/v/v1-2libes.css';
import '../../css/g/g3rbux_4u.css';
import '../../css/a/arjsqib7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wk-zpbcpt"/><path class="v1-2libes"/><path class="g3rbux_4u"/><path class="arjsqib7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:thymeleaf-wordmark" /></template>
