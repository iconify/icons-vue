<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xst33ez6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xst33ez6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zitadel-light" /></template>
