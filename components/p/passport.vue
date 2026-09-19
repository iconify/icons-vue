<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6xcxzbol.css';
import '../../css/w/wdo02gbao.css';
import '../../css/b/bzea6tsoy.css';
import '../../css/q/qq0d7y3ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h6xcxzbol"/><path class="wdo02gbao"/><path class="bzea6tsoy"/><path class="qq0d7y3ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:passport" /></template>
