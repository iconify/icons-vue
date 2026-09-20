<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z64q5ub-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z64q5ub-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-sparkle-sharp-fill" /></template>
