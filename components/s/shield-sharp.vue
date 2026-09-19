<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if1ow3fmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="if1ow3fmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shield-sharp" /></template>
