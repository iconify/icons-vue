<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq3f9327i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yq3f9327i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wifi-signal-full-remix" /></template>
