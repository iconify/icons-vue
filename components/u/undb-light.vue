<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqba5yb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqba5yb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:undb-light" /></template>
