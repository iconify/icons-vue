<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z578n6buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z578n6buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:speaker-loud" /></template>
