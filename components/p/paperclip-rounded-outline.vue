<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ztybb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9ztybb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-outline" /></template>
