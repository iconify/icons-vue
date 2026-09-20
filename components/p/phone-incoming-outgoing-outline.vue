<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld_s7kl1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld_s7kl1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-incoming-outgoing-outline" /></template>
