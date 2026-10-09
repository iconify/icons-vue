<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7qqaciu.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/e/evw_lacsv.css';
import '../../css/p/prfptqbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ci7qqaciu"/><path class="aqsnv9bnd"/><path class="evw_lacsv"/><path class="prfptqbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-plus-20-bold" /></template>
