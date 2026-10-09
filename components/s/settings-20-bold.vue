<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijh-5sqyq.css';
import '../../css/o/okm62lwzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ijh-5sqyq"/><path class="okm62lwzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:settings-20-bold" /></template>
