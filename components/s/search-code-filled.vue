<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyqof_b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyqof_b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:search-code-filled" /></template>
