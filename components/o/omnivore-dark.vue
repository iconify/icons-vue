<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjxm_wlfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjxm_wlfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnivore-dark" /></template>
