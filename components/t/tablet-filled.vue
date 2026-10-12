<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lebm5qx9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lebm5qx9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tablet-filled" /></template>
