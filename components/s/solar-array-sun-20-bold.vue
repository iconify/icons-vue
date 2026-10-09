<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heh8_qbzw.css';
import '../../css/j/jqemctbeh.css';
import '../../css/l/l7fkvo-fr.css';
import '../../css/m/moj4tsily.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="heh8_qbzw"/><path class="jqemctbeh"/><path class="l7fkvo-fr"/><path class="moj4tsily"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-array-sun-20-bold" /></template>
