<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2bc_dbqk.css';
import '../../css/l/lg3s6q7pu.css';
import '../../css/p/pohg4abrz.css';
import '../../css/k/ktlo7wbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b2bc_dbqk"/><path class="lg3s6q7pu"/><path class="pohg4abrz"/><path class="ktlo7wbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pear" /></template>
