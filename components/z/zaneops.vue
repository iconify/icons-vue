<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2cs6yhfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2cs6yhfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zaneops" /></template>
