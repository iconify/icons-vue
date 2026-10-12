<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw1ncuo8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw1ncuo8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-off-filled" /></template>
