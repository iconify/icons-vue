<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2txbcl2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2txbcl2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:writefreely-dark" /></template>
