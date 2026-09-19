<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_zm7infu.css';
import '../../css/j/jzvydlbca.css';
import '../../css/t/t2jzbtbga.css';
import '../../css/c/clmzz-59m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_zm7infu"/><path class="jzvydlbca"/><path class="t2jzbtbga"/><path class="clmzz-59m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:octopus" /></template>
