<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df2i0cbrv.css';
import '../../css/m/m0c34ebvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="df2i0cbrv"/><path clip-rule="evenodd" class="m0c34ebvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-light" /></template>
