<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5vx4lykm.css';
import '../../css/i/iwzjusbjd.css';
import '../../css/s/sh06c0bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5vx4lykm"/><path class="iwzjusbjd"/><path class="sh06c0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-check-20-bold" /></template>
