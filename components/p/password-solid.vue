<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipfz-qbde.css';
import '../../css/l/l0z5z-bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ipfz-qbde"/><path clip-rule="evenodd" class="l0z5z-bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:password-solid" /></template>
