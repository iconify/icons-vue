<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evge9_brb.css';
import '../../css/j/jdicwcndp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evge9_brb"/><path class="jdicwcndp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solidcraft-dark" /></template>
