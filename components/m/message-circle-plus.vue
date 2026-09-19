<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykj3jqd3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykj3jqd3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-circle-plus" /></template>
