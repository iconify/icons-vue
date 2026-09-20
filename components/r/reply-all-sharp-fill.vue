<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxh_3sbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxh_3sbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-all-sharp-fill" /></template>
