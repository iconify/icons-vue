<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6b239zsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6b239zsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unifi-voucher-site-light" /></template>
