<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgbaqzbcl.css';
import '../../css/y/yurlis35z.css';
import '../../css/e/efp1h8bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgbaqzbcl"/><path class="yurlis35z"/><path class="efp1h8bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailrise-dark" /></template>
