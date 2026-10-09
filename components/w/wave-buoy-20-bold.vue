<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1qfvnbiq.css';
import '../../css/w/w7seexb0p.css';
import '../../css/m/m2f1aybya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i1qfvnbiq"/><path class="w7seexb0p"/><path class="m2f1aybya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-buoy-20-bold" /></template>
