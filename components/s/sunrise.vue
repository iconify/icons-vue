<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6vu2n_it.css';
import '../../css/q/qr2jzwbvc.css';
import '../../css/t/tajbw3b6k.css';
import '../../css/m/mmwsdobmn.css';
import '../../css/h/hfz3b8b5m.css';
import '../../css/c/c7ayd-b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g6vu2n_it"/><path class="qr2jzwbvc"/><path class="tajbw3b6k"/><path class="mmwsdobmn"/><path class="hfz3b8b5m"/><path class="c7ayd-b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sunrise" /></template>
