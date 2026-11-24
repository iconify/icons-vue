<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhzupix5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhzupix5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:passonce-dark" /></template>
