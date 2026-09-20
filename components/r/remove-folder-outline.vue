<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uktee8nma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uktee8nma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remove-folder-outline" /></template>
