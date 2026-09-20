<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzxkhmb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzxkhmb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:table-lamp-2" /></template>
