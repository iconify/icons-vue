<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7iq_fa2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r7iq_fa2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xmpp-dark" /></template>
