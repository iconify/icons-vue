<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fgn4zzbxd.css';
import '../../css/b/b7b6egbjf.css';
import '../../css/n/nvukm8ejr.css';
import '../../css/n/nshm1nb1i.css';
import '../../css/d/dx6zqbcdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fgn4zzbxd"/><path class="b7b6egbjf"/><path class="nvukm8ejr"/><path class="nshm1nb1i"/><path class="dx6zqbcdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:robot" /></template>
