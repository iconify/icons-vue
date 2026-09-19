<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taglg-g8l.css';
import '../../css/d/d596urw4w.css';
import '../../css/f/fosmaibkm.css';
import '../../css/o/o4_qjwblv.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 taglg-g8l"/><path class="clr-i-outline clr-i-outline-path-2 d596urw4w"/><path class="clr-i-outline clr-i-outline-path-3 fosmaibkm"/><path class="clr-i-outline clr-i-outline-path-4 o4_qjwblv"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:wand-line" /></template>
