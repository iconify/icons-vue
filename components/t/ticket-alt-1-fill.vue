<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e58mt0o4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e58mt0o4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ticket-alt-1-fill" /></template>
