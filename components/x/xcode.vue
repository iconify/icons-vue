<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9t7r_beh.css';
import '../../css/o/ot-ja0ext.css';
import '../../css/x/xzna_cbux.css';
import '../../css/s/suv371o5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c9t7r_beh"/><g class="ot-ja0ext"><path transform="matrix(.50714 -.15926 .15877 .5054 2.596 1.629)" class="xzna_cbux"/><path transform="matrix(.50714 -.15926 .15877 .5054 2.596 1.629)" class="suv371o5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:xcode" /></template>
