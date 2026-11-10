<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux6p4ubfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux6p4ubfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-x-mark-solid" /></template>
