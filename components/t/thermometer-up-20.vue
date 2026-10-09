<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zve7bwi.css';
import '../../css/l/lrf20th3l.css';
import '../../css/q/qekov_6lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6zve7bwi"/><path class="lrf20th3l"/><path class="qekov_6lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-up-20" /></template>
