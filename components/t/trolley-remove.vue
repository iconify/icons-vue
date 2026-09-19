<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xv9bpkifw.css';
import '../../css/o/o8cfnsgvu.css';
import '../../css/w/w5t6kcbgd.css';
import '../../css/z/z-fdbxbxg.css';
import '../../css/b/bxrmdablx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><g transform="translate(4 12)" class="cuyn6tgcc"><circle class="xv9bpkifw"/><ellipse class="o8cfnsgvu"/></g><path class="w5t6kcbgd"/><path class="z-fdbxbxg"/><path class="bxrmdablx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:trolley-remove" /></template>
