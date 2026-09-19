<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm_2r6lbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zm_2r6lbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:noentrysign" /></template>
