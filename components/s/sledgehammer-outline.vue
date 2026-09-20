<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr-v_6l2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr-v_6l2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sledgehammer-outline" /></template>
