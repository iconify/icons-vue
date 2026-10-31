<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf7dm3ncm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lf7dm3ncm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left-solid" /></template>
