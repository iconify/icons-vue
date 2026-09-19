<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9whnsu6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9whnsu6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-snooze" /></template>
