<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nphcgbcmt.css';
import '../../css/k/k9no-9t3l.css';
import '../../css/f/fmbn5ubnp.css';
import '../../css/i/io-bp4hes.css';
import '../../css/r/rp2xrbvey.css';
import '../../css/x/xlf8yxbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nphcgbcmt"/><path class="k9no-9t3l"/><path class="fmbn5ubnp"/><path class="io-bp4hes"/><path class="rp2xrbvey"/><path class="xlf8yxbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-id-bold-duotone" /></template>
