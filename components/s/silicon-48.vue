<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8mtjico.css';
import '../../css/h/hzl2uybek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pa8mtjico"/><path class="hzl2uybek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silicon-48" /></template>
