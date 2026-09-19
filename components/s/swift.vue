<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2gnuus1q.css';
import '../../css/u/uvu1bzkib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u2gnuus1q"/><path class="uvu1bzkib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:swift" /></template>
