<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf-lmqboi.css';
import '../../css/c/c8c_oybxb.css';
import '../../css/v/v--izksva.css';
import '../../css/v/vrqg2kbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lf-lmqboi"/><path class="c8c_oybxb"/><path class="v--izksva"/><path class="vrqg2kbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sim-card-20-bold" /></template>
