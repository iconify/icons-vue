<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sho0vcbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sho0vcbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mozilla-vpn" /></template>
