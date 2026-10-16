<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8s-z80le.css';
import '../../css/p/pkm70y_4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8s-z80le"/><path class="pkm70y_4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-dots-48-bold" /></template>
