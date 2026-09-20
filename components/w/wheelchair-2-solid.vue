<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg2s2rtgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tg2s2rtgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wheelchair-2-solid" /></template>
