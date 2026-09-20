<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi9pjnbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9pjnbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:menu-2-filled" /></template>
