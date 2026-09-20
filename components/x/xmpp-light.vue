<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvm3lumsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cvm3lumsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xmpp-light" /></template>
