<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8hbi9srx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8hbi9srx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-cancel" /></template>
