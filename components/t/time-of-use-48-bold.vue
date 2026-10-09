<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghq0elqau.css';
import '../../css/f/fzoldhk-f.css';
import '../../css/f/fz14dobdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghq0elqau"/><path class="fzoldhk-f"/><path class="fz14dobdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:time-of-use-48-bold" /></template>
