<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2zihunpi.css';
import '../../css/n/nuiom3xgn.css';
import '../../css/u/u07xh6bzl.css';
import '../../css/r/ra5mw5bki.css';
import '../../css/i/ip8mjmxtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t2zihunpi"/><path class="nuiom3xgn"/><path class="u07xh6bzl"/><path class="ra5mw5bki"/><path class="ip8mjmxtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sabnzbd" /></template>
