<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7v6m7bjd.css';
import '../../css/i/ibfphwlbh.css';
import '../../css/l/ls2ev_smn.css';
import '../../css/a/aehkirbxj.css';
import '../../css/r/rmauuzbau.css';
import '../../css/g/gdw8bzbhd.css';
import '../../css/g/g6wt0dbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7v6m7bjd wm-shadow"/><path class="ibfphwlbh"/><path class="ls2ev_smn"/><path class="aehkirbxj"/><path class="rmauuzbau"/><path class="gdw8bzbhd wm-shine"/><path class="g6wt0dbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:sigma" /></template>
