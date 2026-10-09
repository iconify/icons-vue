<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mniqmdgfa.css';
import '../../css/o/onpzv9a2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mniqmdgfa"/><path class="onpzv9a2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-48" /></template>
