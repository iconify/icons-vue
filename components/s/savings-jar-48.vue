<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u54wvrbhl.css';
import '../../css/w/w1i6zjb6u.css';
import '../../css/a/ahp9osbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u54wvrbhl"/><path class="w1i6zjb6u"/><path class="ahp9osbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:savings-jar-48" /></template>
