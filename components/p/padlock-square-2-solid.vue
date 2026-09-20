<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li2u5xh7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="li2u5xh7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:padlock-square-2-solid" /></template>
