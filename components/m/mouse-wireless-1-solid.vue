<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5jmgibkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v5jmgibkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mouse-wireless-1-solid" /></template>
