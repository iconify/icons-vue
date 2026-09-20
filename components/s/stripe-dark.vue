<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm_xptbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sm_xptbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stripe-dark" /></template>
