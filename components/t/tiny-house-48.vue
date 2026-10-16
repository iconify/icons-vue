<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gap9t0gmp.css';
import '../../css/t/tyua78b5m.css';
import '../../css/d/dvftmgbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gap9t0gmp"/><path class="tyua78b5m"/><path class="dvftmgbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tiny-house-48" /></template>
