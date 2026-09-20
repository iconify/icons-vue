<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx2z2_bmy.css';
import '../../css/a/a8dw5zbze.css';
import '../../css/n/n05rifjbu.css';
import '../../css/o/o4--dac7r.css';
import '../../css/j/jamdwgbff.css';
import '../../css/h/hjczt2g6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yx2z2_bmy"/><path class="a8dw5zbze"/><path class="n05rifjbu"/><circle class="o4--dac7r"/><path class="jamdwgbff"/><path class="hjczt2g6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:spouting-orca" /></template>
