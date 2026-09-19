<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdu0vibli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pdu0vibli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mental-health" /></template>
