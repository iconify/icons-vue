<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0yys_sjp.css';
import '../../css/p/pkv646nkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0yys_sjp"/><path class="pkv646nkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-vibrate-48" /></template>
