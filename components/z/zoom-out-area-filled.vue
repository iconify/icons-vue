<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifegf4bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifegf4bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-out-area-filled" /></template>
