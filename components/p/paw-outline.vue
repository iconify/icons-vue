<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixn_37yhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixn_37yhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:paw-outline" /></template>
