<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w64q5rbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w64q5rbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-outline" /></template>
