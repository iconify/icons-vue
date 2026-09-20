<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjk-t8h4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjk-t8h4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-spreadsheet-light" /></template>
