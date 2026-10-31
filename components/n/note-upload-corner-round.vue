<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy6azchko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy6azchko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-upload-corner-round" /></template>
