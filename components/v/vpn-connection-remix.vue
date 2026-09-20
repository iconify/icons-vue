<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng6nzyr8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ng6nzyr8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:vpn-connection-remix" /></template>
