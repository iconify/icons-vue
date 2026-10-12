<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqwamo7sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqwamo7sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-filled" /></template>
