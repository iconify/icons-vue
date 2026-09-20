<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omnh2jb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omnh2jb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sunrise" /></template>
