<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei1xe8bei.css';
import '../../css/i/i2eqxibtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ei1xe8bei"/><path class="i2eqxibtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:neon-wordmark" /></template>
