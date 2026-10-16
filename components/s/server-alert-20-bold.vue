<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5vx4lykm.css';
import '../../css/i/iwzjusbjd.css';
import '../../css/k/kapshj_5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5vx4lykm"/><path class="iwzjusbjd"/><path class="kapshj_5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-alert-20-bold" /></template>
