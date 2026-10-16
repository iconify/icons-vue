<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj6ml7n0t.css';
import '../../css/u/ufkna9bqo.css';
import '../../css/j/jj0jprbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kj6ml7n0t"/><path class="ufkna9bqo"/><path class="jj0jprbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:strategy-20" /></template>
