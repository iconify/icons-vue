<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqroeob7g.css';
import '../../css/i/il713jb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":47.9};
const content = `<path class="kqroeob7g"/><path class="il713jb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:subway" /></template>
