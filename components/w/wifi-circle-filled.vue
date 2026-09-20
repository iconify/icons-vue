<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/i/ivjvz2eii.css';
import '../../css/g/g-492zb_b.css';
import '../../css/j/jkzcixbgu.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGA3MGae6t"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="g-492zb_b"/><path class="jkzcixbgu"/></g></mask></defs><circle mask="url(#SVGA3MGae6t)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:wifi-circle-filled" /></template>
