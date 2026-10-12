<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co7oz4bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co7oz4bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-warning-filled" /></template>
