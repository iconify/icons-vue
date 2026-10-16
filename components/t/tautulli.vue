<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwtlcbcgl.css';
import '../../css/c/cbw46ub7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":298.961,"height":300};
const content = `<path class="pwtlcbcgl"/><path class="cbw46ub7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tautulli" /></template>
