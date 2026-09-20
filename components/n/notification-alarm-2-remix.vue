<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj-nmb40m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj-nmb40m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:notification-alarm-2-remix" /></template>
