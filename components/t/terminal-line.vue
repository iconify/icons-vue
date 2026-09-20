<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn_sgnaqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn_sgnaqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:terminal-line" /></template>
