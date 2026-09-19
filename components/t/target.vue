<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbp2n_b0d.css';
import '../../css/w/wyddhdbvg.css';
import '../../css/w/weozcygjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="gbp2n_b0d"/><path class="wyddhdbvg"/><circle class="weozcygjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:target" /></template>
