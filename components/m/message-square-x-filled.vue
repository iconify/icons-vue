<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsgjjsj8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lsgjjsj8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-x-filled" /></template>
