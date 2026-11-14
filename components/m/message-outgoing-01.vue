<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q54rqbhcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q54rqbhcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-outgoing-01" /></template>
