<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/accicg2ns.css';
import '../../css/l/ldtpmn0ux.css';
import '../../css/l/l52qpcb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="accicg2ns"/><path class="ldtpmn0ux"/><path class="l52qpcb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-light" /></template>
