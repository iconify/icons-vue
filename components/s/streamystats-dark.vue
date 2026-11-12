<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyop2kbkj.css';
import '../../css/s/sna9uxb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyop2kbkj"/><path class="sna9uxb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamystats-dark" /></template>
