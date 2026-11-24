<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo1c8-b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo1c8-b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-filled" /></template>
