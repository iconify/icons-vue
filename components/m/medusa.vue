<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okzc-_smy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okzc-_smy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medusa" /></template>
