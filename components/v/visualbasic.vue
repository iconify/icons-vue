<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laiykvrmt.css';
import '../../css/g/gqsxbnbla.css';
import '../../css/s/swauynb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="laiykvrmt"/><path class="gqsxbnbla"/><path class="swauynb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:visualbasic" /></template>
