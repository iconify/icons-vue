<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb5dzpbru.css';
import '../../css/h/h8kldlbhr.css';
import '../../css/n/n-seofb-c.css';
import '../../css/m/m94ggluil.css';
import '../../css/p/pqto13t3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb5dzpbru"/><path class="h8kldlbhr"/><path class="n-seofb-c"/><path class="m94ggluil"/><path class="pqto13t3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:medicalmask" /></template>
