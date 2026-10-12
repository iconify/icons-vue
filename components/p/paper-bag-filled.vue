<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfl8apr-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfl8apr-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paper-bag-filled" /></template>
