<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nziseix1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nziseix1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vmware-esx-light" /></template>
