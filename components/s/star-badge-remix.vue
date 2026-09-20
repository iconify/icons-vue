<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7pqyepvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t7pqyepvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:star-badge-remix" /></template>
