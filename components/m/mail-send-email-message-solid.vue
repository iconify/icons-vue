<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3bqa_bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3bqa_bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-send-email-message-solid" /></template>
