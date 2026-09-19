<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crgdrwxoi.css';
import '../../css/t/t6i-1mb8p.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged crgdrwxoi"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged t6i-1mb8p"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:power-outline-badged" /></template>
