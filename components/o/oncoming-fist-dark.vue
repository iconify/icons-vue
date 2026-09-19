<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2rk88aae.css';
import '../../css/g/gc7lh6bwa.css';
import '../../css/v/v48dolbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="n2rk88aae"/><path class="gc7lh6bwa"/><path class="v48dolbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:oncoming-fist-dark" /></template>
