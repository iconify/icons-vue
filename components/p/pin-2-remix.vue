<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzve78bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bzve78bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pin-2-remix" /></template>
