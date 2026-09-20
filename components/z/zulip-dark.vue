<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-blenb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-blenb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zulip-dark" /></template>
