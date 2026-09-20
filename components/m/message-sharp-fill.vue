<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ylmgcko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ylmgcko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-sharp-fill" /></template>
