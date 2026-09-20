<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eanui2ium.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eanui2ium"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plikshare-dark" /></template>
