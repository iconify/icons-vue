<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgw988bsm.css';
import '../../css/g/gn5j3-b2t.css';
import '../../css/u/u11od-bgv.css';
import '../../css/f/fzy27luea.css';
import '../../css/e/ejk1ck6md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgw988bsm"/><path class="gn5j3-b2t"/><path class="u11od-bgv"/><path class="fzy27luea"/><path class="ejk1ck6md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mini-qr" /></template>
