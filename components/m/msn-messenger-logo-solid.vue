<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic9xufl-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic9xufl-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:msn-messenger-logo-solid" /></template>
