<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce0cywmuu.css';
import '../../css/p/pf7rljwtp.css';
import '../../css/x/xl8x9eggy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0cywmuu"/><path class="pf7rljwtp"/><path class="xl8x9eggy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-lock-48-bold" /></template>
