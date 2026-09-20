<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjwqrtb-a.css';
import '../../css/e/e4du2zpbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xjwqrtb-a"/><path class="e4du2zpbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privadovpn" /></template>
