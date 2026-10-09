<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqy86tb6z.css';
import '../../css/s/sfnrnobbo.css';
import '../../css/r/r1uy14ztu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uqy86tb6z"/><path class="sfnrnobbo"/><path class="r1uy14ztu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-call-48-bold" /></template>
