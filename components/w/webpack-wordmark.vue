<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mft8bat.css';
import '../../css/f/fr5171a8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l1mft8bat"/><path class="fr5171a8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:webpack-wordmark" /></template>
