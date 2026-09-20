<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgfd5rbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgfd5rbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openspeedtest-dark" /></template>
