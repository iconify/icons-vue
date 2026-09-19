<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6aq9l9vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6aq9l9vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:message-caption-outline" /></template>
