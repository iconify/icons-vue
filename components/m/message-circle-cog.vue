<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt7dxsrju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt7dxsrju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-cog" /></template>
