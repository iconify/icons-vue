<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpie12blh.css';
import '../../css/w/w092a3gwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpie12blh"/><path class="w092a3gwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zoho-mail" /></template>
