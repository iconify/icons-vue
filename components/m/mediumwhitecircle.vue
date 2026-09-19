<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3p8w_7pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="m3p8w_7pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mediumwhitecircle" /></template>
