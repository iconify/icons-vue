<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-l7bsb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-l7bsb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unifi-voucher-site-dark" /></template>
