<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsg5j7ibl.css';
import '../../css/s/szifr4b9l.css';
import '../../css/u/un755_b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="szifr4b9l"/><path class="un755_b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reload-circle-outline" /></template>
