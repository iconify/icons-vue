<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqq4spbzl.css';
import '../../css/e/ej3ft6qzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqq4spbzl"/><path class="ej3ft6qzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:weightlifitng" /></template>
