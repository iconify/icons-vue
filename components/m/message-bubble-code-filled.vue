<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfv7tub0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfv7tub0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-code-filled" /></template>
