<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3hezabwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r3hezabwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-activation-1-solid" /></template>
