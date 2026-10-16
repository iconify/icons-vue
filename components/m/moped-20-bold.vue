<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq2op-bzr.css';
import '../../css/r/rucx1acha.css';
import '../../css/p/pkqibmblv.css';
import '../../css/k/kg7y9mgki.css';
import '../../css/s/sy560ubcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gq2op-bzr"/><path class="rucx1acha"/><path class="pkqibmblv"/><path class="kg7y9mgki"/><path class="sy560ubcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moped-20-bold" /></template>
