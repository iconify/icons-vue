<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9mgzabny.css';
import '../../css/p/p0dsglbia.css';
import '../../css/u/uj8cponlm.css';
import '../../css/u/u2ephhbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k9mgzabny"/><path class="p0dsglbia"/><path class="uj8cponlm"/><path class="u2ephhbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vacuum-20" /></template>
