<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7dup-bsh.css';
import '../../css/m/mupntswkv.css';
import '../../css/c/cppppzbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7dup-bsh"/><path class="mupntswkv"/><path class="cppppzbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-angle-48-bold" /></template>
