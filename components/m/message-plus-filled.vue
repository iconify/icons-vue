<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc9q8fb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc9q8fb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-plus-filled" /></template>
