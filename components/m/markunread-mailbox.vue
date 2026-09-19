<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-7gfo8if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":472};
const content = `<path class="h-7gfo8if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:markunread-mailbox" /></template>
