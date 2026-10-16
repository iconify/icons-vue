<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lycgy4bwn.css';
import '../../css/c/cnifdczmc.css';
import '../../css/n/nzxup3_0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lycgy4bwn"/><path class="cnifdczmc"/><path class="nzxup3_0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safety-boot-48-bold" /></template>
