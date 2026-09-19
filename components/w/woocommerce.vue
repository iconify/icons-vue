<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd415ib1g.css';
import '../../css/h/hl-46jmiu.css';
import '../../css/c/cpcuf9xkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fd415ib1g"/><path class="hl-46jmiu"/><path class="cpcuf9xkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:woocommerce" /></template>
