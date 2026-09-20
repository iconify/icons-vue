<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvi1h665o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kvi1h665o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:smiley-drool-remix" /></template>
