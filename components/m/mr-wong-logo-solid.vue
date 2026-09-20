<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix5upybjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ix5upybjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mr-wong-logo-solid" /></template>
