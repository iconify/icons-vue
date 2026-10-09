<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps4o7zbjt.css';
import '../../css/i/ihbry8iqd.css';
import '../../css/l/l-vbyx9dn.css';
import '../../css/z/z-gc4bcqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ps4o7zbjt"/><path class="ihbry8iqd"/><path class="l-vbyx9dn"/><path class="z-gc4bcqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-canopy-48-bold" /></template>
