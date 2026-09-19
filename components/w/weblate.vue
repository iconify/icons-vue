<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq44mglgu.css';
import '../../css/s/sobdcvb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cq44mglgu weblate-plain-st0"/><path class="sobdcvb0f weblate-plain-st0"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:weblate" /></template>
