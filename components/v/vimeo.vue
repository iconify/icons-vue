<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7d28tslr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":650,"height":679};
const content = `<path class="i7d28tslr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:vimeo" /></template>
