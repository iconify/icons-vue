<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vjtxb2bkn.css';
import '../../css/y/y77s6pbru.css';
import '../../css/y/yu4jrjx8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vjtxb2bkn"/><path class="y77s6pbru"/><path class="yu4jrjx8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:palms-up-together-medium-dark" /></template>
