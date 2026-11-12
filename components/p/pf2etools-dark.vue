<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twe_8u5bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="twe_8u5bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pf2etools-dark" /></template>
