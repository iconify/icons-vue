<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2nhrni-v.css';
import '../../css/a/az532d-fz.css';
import '../../css/z/z04drlb1l.css';
import '../../css/q/qdzbtslrm.css';
import '../../css/r/rkh9jmd8r.css';
import '../../css/m/muedlcc7n.css';
import '../../css/h/h8810e80n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="l2nhrni-v"/><path class="az532d-fz"/><g class="z04drlb1l"><path class="qdzbtslrm"/><path class="rkh9jmd8r"/><path class="muedlcc7n"/><path class="h8810e80n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:snake" /></template>
