<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx6btm5lw.css';
import '../../css/v/vm-h8y56c.css';
import '../../css/i/iaax7gb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bx6btm5lw"/><path class="vm-h8y56c"/><path class="iaax7gb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pumped-hydro-20-bold" /></template>
