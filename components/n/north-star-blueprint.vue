<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/b-fdzdbra.css';
import '../../css/k/kn4az7bnd.css';
import '../../css/o/o87q8k2ri.css';
import '../../css/o/orfvm667v.css';
import '../../css/u/u0km1qbun.css';
import '../../css/m/mj4c7uw7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="b-fdzdbra wm-deco"/><path class="kn4az7bnd wm-deco"/><path class="o87q8k2ri wm-deco"/><path class="orfvm667v wm-k"/><path class="u0km1qbun wm-a"/><path class="mj4c7uw7s wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:north-star-blueprint" /></template>
