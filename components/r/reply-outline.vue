<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd7edwb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd7edwb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:reply-outline" /></template>
