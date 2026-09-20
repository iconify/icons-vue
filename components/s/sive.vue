<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp_bqbcum.css';
import '../../css/s/s9t-vws4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vp_bqbcum"/><path class="s9t-vws4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sive" /></template>
