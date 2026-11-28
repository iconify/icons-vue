<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfb3xu9nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfb3xu9nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-code-solid" /></template>
