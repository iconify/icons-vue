<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntqwcibqp.css';
import '../../css/f/fk05w0vld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntqwcibqp"/><path class="fk05w0vld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:users-round-filled" /></template>
