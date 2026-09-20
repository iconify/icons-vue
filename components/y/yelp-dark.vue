<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyc2s6b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyc2s6b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yelp-dark" /></template>
