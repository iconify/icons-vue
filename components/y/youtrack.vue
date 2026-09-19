<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgymii1sy.css';
import '../../css/d/dllvb5bsq.css';
import '../../css/p/pc9gqgbnv.css';
import '../../css/p/pws7zcb7t.css';
import '../../css/l/l1xa_ebuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGUsyxJbDL" x1="-.102" x2="64.053" y1="32" y2="32" gradientTransform="scale(1.99998)" gradientUnits="userSpaceOnUse"><stop class="vgymii1sy"/><stop offset=".97" class="dllvb5bsq"/></linearGradient></defs><path fill="url(#SVGUsyxJbDL)" class="pc9gqgbnv"/><path class="pws7zcb7t"/><path class="l1xa_ebuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:youtrack" /></template>
