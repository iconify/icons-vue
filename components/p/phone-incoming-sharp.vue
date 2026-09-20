<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7y1jabpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7y1jabpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-incoming-sharp" /></template>
