<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0_o47byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0_o47byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:syncthing-dark" /></template>
