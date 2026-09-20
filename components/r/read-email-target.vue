<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew0ia5buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ew0ia5buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:read-email-target" /></template>
