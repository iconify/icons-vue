<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxia6zz2s.css';
import '../../css/a/afzjcibgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rxia6zz2s"/><path class="afzjcibgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pi-20-bold" /></template>
