<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qonlf4bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qonlf4bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:travelperk-dark" /></template>
