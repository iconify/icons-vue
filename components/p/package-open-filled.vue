<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfm7feroz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfm7feroz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-open-filled" /></template>
