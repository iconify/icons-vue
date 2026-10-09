<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7vtw8pys.css';
import '../../css/w/w00mpvx0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d7vtw8pys"/><path class="w00mpvx0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subsea-cable-20" /></template>
