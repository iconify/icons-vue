<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8r2o0cup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8r2o0cup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nodecosmos-light" /></template>
