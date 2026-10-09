<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gulry0b2k.css';
import '../../css/j/jfdl44b3i.css';
import '../../css/b/bfk_0tp3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gulry0b2k"/><path class="jfdl44b3i"/><path class="bfk_0tp3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:window-48" /></template>
