<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhh78xbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhh78xbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-code-filled" /></template>
