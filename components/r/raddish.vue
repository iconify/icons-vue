<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo_lgwbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qo_lgwbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:raddish" /></template>
