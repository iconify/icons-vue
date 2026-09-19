<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdp49sb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdp49sb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:mailbox" /></template>
