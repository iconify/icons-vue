<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gax-3p3_e.css';
import '../../css/c/cz41hf7gw.css';
import '../../css/d/ds0r57bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gax-3p3_e"/><path class="cz41hf7gw"/><path class="ds0r57bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sourceengine-wordmark" /></template>
