<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yljdd-biq.css';
import '../../css/c/cqlg1elow.css';
import '../../css/m/mqymo7s1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yljdd-biq"/><path class="cqlg1elow"/><path class="mqymo7s1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radicle-light" /></template>
