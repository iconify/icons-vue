<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxc27i0rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sxc27i0rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-application-2-remix" /></template>
