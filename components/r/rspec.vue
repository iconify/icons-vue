<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzk_u8uvf.css';
import '../../css/h/hcys5pimr.css';
import '../../css/c/cltfdlb1g.css';
import '../../css/m/m8-3fg9ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="jzk_u8uvf"/><path class="hcys5pimr"/><path class="cltfdlb1g"/><path class="m8-3fg9ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rspec" /></template>
