<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1xeb4bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1xeb4bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-lines-sharp" /></template>
