<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8fh6bcax.css';
import '../../css/b/bxc0s0-hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s8fh6bcax"/><path class="bxc0s0-hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:woocommerce" /></template>
