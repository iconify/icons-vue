<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpw9o4b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpw9o4b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-ellipsis-filled" /></template>
