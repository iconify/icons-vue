<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpcvxrp2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rpcvxrp2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-dots-filled" /></template>
