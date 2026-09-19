<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en6iffg9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="en6iffg9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rightborder" /></template>
