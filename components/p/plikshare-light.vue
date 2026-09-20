<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmi_zrsne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmi_zrsne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plikshare-light" /></template>
