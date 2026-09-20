<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sibkcjb8c.css';
import '../../css/i/ii43a9b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sibkcjb8c"/><path class="ii43a9b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-2000" /></template>
