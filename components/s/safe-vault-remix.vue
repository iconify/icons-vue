<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlc32acft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dlc32acft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:safe-vault-remix" /></template>
