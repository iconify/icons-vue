<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtlo8iikr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtlo8iikr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-2-fill" /></template>
