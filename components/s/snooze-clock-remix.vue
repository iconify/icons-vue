<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuczs7xit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nuczs7xit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:snooze-clock-remix" /></template>
