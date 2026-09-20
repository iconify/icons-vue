<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5htat2ww.css';
import '../../css/t/tiikn06-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="d5htat2ww"/><path class="tiikn06-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wireguard" /></template>
