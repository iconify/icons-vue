<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxln9bcuq.css';
import '../../css/g/gcac09b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lxln9bcuq"/><path class="gcac09b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typo3-wordmark" /></template>
