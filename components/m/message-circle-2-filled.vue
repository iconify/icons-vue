<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krw0w3bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krw0w3bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-2-filled" /></template>
