<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf9bi_bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gf9bi_bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pyre" /></template>
