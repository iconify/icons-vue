<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkj04estn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pkj04estn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:voicemail-16" /></template>
