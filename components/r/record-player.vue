<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l1yh7mbll.css';
import '../../css/d/dqi242g4v.css';
import '../../css/f/frm_a4bvr.css';
import '../../css/b/bpz45z7pg.css';
import '../../css/i/iqfyq3i9d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQyARHclC"><g class="ft5dv1b6b"><rect class="l1yh7mbll"/><path class="dqi242g4v"/><circle class="frm_a4bvr"/><circle class="bpz45z7pg"/><path class="iqfyq3i9d"/></g></mask></defs><path mask="url(#SVGQyARHclC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:record-player" /></template>
