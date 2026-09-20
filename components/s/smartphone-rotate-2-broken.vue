<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j44k1ormw.css';
import '../../css/m/mw5i2qouq.css';
import '../../css/h/hal8f3bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j44k1ormw"/><path class="mw5i2qouq"/><path class="hal8f3bya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-rotate-2-broken" /></template>
