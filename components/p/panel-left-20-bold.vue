<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkpulpb9y.css';
import '../../css/a/acc7t232x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="acc7t232x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-20-bold" /></template>
