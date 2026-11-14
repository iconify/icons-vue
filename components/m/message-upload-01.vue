<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/javag0hlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="javag0hlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-upload-01" /></template>
