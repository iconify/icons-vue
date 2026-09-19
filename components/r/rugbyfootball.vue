<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2bjk7byt.css';
import '../../css/c/c33hiv2aq.css';
import '../../css/s/srb0o_b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2bjk7byt"/><path class="c33hiv2aq"/><path class="srb0o_b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:rugbyfootball" /></template>
