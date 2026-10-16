<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccnyeob1g.css';
import '../../css/i/i3bujsneb.css';
import '../../css/m/mccycacnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ccnyeob1g"/><path class="i3bujsneb"/><path class="mccycacnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reply-all-20" /></template>
