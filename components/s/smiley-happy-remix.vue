<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgtdl3gbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kgtdl3gbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-happy-remix" /></template>
