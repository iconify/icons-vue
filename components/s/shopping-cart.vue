<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qlk5m1b8o.css';
import '../../css/p/pzuhhh1if.css';
import '../../css/p/pupkd_1ls.css';
import '../../css/j/jbkl3jbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qlk5m1b8o"/><path class="pzuhhh1if"/><circle class="pupkd_1ls"/><circle class="jbkl3jbof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:shopping-cart" /></template>
