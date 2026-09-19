<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xvhpxbc1d.css';
import '../../css/k/k0soy3mpv.css';
import '../../css/u/ua7h0o40v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="xvhpxbc1d"/><path class="k0soy3mpv"/><circle class="ua7h0o40v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:wallet-one" /></template>
