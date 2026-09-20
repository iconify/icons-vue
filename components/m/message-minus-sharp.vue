<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwermfbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwermfbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-minus-sharp" /></template>
