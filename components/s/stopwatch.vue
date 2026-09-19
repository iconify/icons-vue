<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amlfk0b-w.css';
import '../../css/m/myx56ib_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="amlfk0b-w"/><path class="myx56ib_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:stopwatch" /></template>
