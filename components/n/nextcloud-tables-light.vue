<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2a7lnupb.css';
import '../../css/i/igo6zo3_s.css';
import '../../css/s/s36agfsxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t2a7lnupb"/><path clip-rule="evenodd" class="igo6zo3_s"/><path clip-rule="evenodd" class="s36agfsxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-tables-light" /></template>
