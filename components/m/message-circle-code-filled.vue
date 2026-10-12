<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuwyr7tqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tuwyr7tqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-code-filled" /></template>
