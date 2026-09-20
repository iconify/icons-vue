<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezof65bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezof65bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-path-filled" /></template>
