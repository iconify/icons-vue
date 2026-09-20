<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujw1_grww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ujw1_grww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:puppy" /></template>
