<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlv2fmbfj.css';
import '../../css/u/u1l779tda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlv2fmbfj"/><path class="u1l779tda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pomerium" /></template>
