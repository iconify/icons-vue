<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd_clobel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nd_clobel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:monica-light" /></template>
