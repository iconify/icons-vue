<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5hoe7b8s.css';
import '../../css/e/ea0j21kww.css';
import '../../css/v/ve4jb3chp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5hoe7b8s"/><path class="ea0j21kww"/><path class="ve4jb3chp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-one-48" /></template>
