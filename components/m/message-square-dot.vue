<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh_cvu5cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_cvu5cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-dot" /></template>
