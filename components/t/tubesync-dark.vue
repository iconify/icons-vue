<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0qpnbcmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0qpnbcmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tubesync-dark" /></template>
