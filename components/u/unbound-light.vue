<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa761w5ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa761w5ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unbound-light" /></template>
