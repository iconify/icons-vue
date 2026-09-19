<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl04g7bka.css';
import '../../css/u/uffvvac3n.css';
import '../../css/z/ze1765b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pl04g7bka"/><path class="uffvvac3n"/><path class="ze1765b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:version" /></template>
