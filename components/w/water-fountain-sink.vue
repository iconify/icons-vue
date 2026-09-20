<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwe-sk3re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwe-sk3re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:water-fountain-sink" /></template>
