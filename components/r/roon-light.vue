<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anb_2obmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anb_2obmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roon-light" /></template>
