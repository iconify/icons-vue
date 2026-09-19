<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/daiwxftqz.css';
import '../../css/s/sjqj356qt.css';
import '../../css/p/pgx2ghbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="daiwxftqz"/><path class="sjqj356qt"/><path class="pgx2ghbjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:tooth" /></template>
