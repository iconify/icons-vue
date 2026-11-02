<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgvzp1bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgvzp1bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-plus-fill" /></template>
