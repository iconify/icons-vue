<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st-nb-bnw.css';
import '../../css/t/tiq8xcncs.css';
import '../../css/i/irdsaebul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="st-nb-bnw"/><path class="tiq8xcncs"/><path class="irdsaebul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:megaphone-20" /></template>
