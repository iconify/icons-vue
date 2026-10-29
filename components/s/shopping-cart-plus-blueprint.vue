<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p15i5rb8r.css';
import '../../css/a/aqgqxc--o.css';
import '../../css/v/v_g7r_1us.css';
import '../../css/o/ocnol1b_l.css';
import '../../css/u/utqgvykzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p15i5rb8r wm-deco"/><path class="aqgqxc--o wm-deco"/><path class="v_g7r_1us wm-deco"/><path class="ocnol1b_l wm-k"/><path class="utqgvykzx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shopping-cart-plus-blueprint" /></template>
