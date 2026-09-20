<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq17i1_qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eq17i1_qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:reply-to-message-typing-remix" /></template>
