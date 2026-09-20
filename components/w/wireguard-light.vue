<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g64-eqzac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g64-eqzac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wireguard-light" /></template>
