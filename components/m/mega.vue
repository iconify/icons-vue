<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8g8h_b3b.css';
import '../../css/p/p8n6moh0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="s8g8h_b3b"/><path class="p8n6moh0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mega" /></template>
