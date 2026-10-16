<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c59tb1b5l.css';
import '../../css/b/b18xgubfy.css';
import '../../css/o/onc6e2gme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c59tb1b5l"/><path class="b18xgubfy"/><path class="onc6e2gme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:savings-jar-20" /></template>
