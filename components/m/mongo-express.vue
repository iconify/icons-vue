<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsc6fq3ty.css';
import '../../css/s/skmwvibla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<circle class="dsc6fq3ty"/><path class="skmwvibla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mongo-express" /></template>
