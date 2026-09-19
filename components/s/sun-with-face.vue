<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a2kxj3bar.css';
import '../../css/q/q9pd582ie.css';
import '../../css/c/cwqzxbcxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="a2kxj3bar"/><path class="q9pd582ie"/><path class="cwqzxbcxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:sun-with-face" /></template>
