<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu-95cc_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu-95cc_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-up" /></template>
