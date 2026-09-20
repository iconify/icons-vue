<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdfqr6ksx.css';
import '../../css/t/tqdn9_b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdfqr6ksx"/><path class="tqdn9_b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splitpro-dark" /></template>
