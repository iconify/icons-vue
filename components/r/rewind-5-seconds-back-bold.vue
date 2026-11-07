<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikfqmnb8s.css';
import '../../css/a/a4x15ccoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikfqmnb8s"/><path class="a4x15ccoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-5-seconds-back-bold" /></template>
