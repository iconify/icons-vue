<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxmfpebgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxmfpebgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-outgoing-01" /></template>
