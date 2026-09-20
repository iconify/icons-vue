<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v6l89cc8l.css';
import '../../css/r/r2hba1b6t.css';
import '../../css/t/t87r-6f3e.css';
import '../../css/b/bia4v_qno.css';
import '../../css/r/r1zr_yb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v6l89cc8l"/><path class="r2hba1b6t"/><path class="t87r-6f3e"/><circle transform="rotate(-30 18.665 4.768)" class="bia4v_qno"/><ellipse transform="rotate(-30 18.665 4.768)" class="r1zr_yb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-4-broken" /></template>
