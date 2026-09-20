<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnhbskd2a.css';
import '../../css/b/bnsgscc2v.css';
import '../../css/f/f2_b1ubxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tnhbskd2a"/><path class="bnsgscc2v"/><path class="f2_b1ubxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trailarr-dark" /></template>
