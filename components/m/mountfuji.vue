<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qetnckbkp.css';
import '../../css/y/yr13g5spn.css';
import '../../css/d/d_cckzeas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qetnckbkp"/><path class="yr13g5spn"/><path class="d_cckzeas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mountfuji" /></template>
