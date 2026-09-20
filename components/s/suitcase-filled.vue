<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr0pr52nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr0pr52nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suitcase-filled" /></template>
