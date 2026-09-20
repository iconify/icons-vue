<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7y83cc-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7y83cc-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-outline" /></template>
