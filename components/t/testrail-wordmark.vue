<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viy1tfbqb.css';
import '../../css/g/gge4koq5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="viy1tfbqb"/><path class="gge4koq5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:testrail-wordmark" /></template>
