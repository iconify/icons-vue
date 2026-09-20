<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odnm3i3de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odnm3i3de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket-discount" /></template>
