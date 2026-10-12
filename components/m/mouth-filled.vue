<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj690b9-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj690b9-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouth-filled" /></template>
