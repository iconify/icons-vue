<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amn_b-_3e.css';
import '../../css/x/x5mwsacqi.css';
import '../../css/a/ao3oc6kdn.css';
import '../../css/d/dqfgcrbcx.css';
import '../../css/w/wkz0_n5gi.css';
import '../../css/g/gp34679_b.css';
import '../../css/q/q3aj0vory.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="amn_b-_3e"/><path class="x5mwsacqi"/><path class="ao3oc6kdn"/><path class="dqfgcrbcx"/><path class="wkz0_n5gi"/><path class="gp34679_b"/><path class="q3aj0vory"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:woman" /></template>
