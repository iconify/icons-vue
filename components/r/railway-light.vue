<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiz_soink.css';
import '../../css/i/iikk0lbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jiz_soink"/><path class="iikk0lbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:railway-light" /></template>
