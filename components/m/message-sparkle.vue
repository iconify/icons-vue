<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-hg6ob5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-hg6ob5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-sparkle" /></template>
