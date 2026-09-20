<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4hkjobnc.css';
import '../../css/m/moe9y6t0w.css';
import '../../css/g/g62bnqbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4hkjobnc"/><path class="moe9y6t0w"/><path class="g62bnqbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:table" /></template>
