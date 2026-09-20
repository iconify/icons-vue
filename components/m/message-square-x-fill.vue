<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk1kz6c0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk1kz6c0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-x-fill" /></template>
