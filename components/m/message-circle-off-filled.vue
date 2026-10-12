<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtlkh7b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtlkh7b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-off-filled" /></template>
