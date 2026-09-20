<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh64f7b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sh64f7b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sign-at-remix" /></template>
