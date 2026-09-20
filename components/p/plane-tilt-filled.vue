<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u332-vb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u332-vb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-tilt-filled" /></template>
