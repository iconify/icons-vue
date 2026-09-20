<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eatouiyuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eatouiyuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reply-2-outline" /></template>
