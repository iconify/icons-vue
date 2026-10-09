<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keo7l-5me.css';
import '../../css/a/ad8--_xso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="keo7l-5me"/><path class="ad8--_xso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-pin-off-48-bold" /></template>
