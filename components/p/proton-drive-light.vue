<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na8uue77l.css';
import '../../css/d/d8n319blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="na8uue77l"/><path class="d8n319blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-drive-light" /></template>
