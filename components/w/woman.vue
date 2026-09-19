<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0ny04box.css';
import '../../css/t/tbr9lu2nb.css';
import '../../css/f/f1jl3db2y.css';
import '../../css/n/nhsm7xg9n.css';
import '../../css/m/mrgh19axd.css';
import '../../css/d/d08w_z9bm.css';
import '../../css/e/emc_w2bmd.css';
import '../../css/r/rgm-v3b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="v0ny04box"/><path class="tbr9lu2nb"/><path class="f1jl3db2y"/><path class="nhsm7xg9n"/><path class="mrgh19axd"/><path class="d08w_z9bm"/><path class="emc_w2bmd"/><path class="rgm-v3b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:woman" /></template>
