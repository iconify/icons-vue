<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-0n92z7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-0n92z7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-up-left-sharp-fill" /></template>
