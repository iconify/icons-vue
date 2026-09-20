<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkv67qbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fkv67qbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wazuh-light" /></template>
