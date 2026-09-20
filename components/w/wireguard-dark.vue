<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv_3vhb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kv_3vhb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wireguard-dark" /></template>
