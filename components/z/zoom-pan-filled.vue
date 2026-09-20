<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2-x1gb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2-x1gb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-pan-filled" /></template>
