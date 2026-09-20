<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyye1n_ow.css';
import '../../css/m/mkgj1odis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyye1n_ow"/><path class="mkgj1odis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reclaimerr-dark" /></template>
