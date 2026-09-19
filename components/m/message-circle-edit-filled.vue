<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af3v4qk0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af3v4qk0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-edit-filled" /></template>
