<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn_i5xb7j.css';
import '../../css/t/tgvy-8bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bn_i5xb7j"/><path class="tgvy-8bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:webpack" /></template>
