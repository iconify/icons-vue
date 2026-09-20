<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2vxt3bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2vxt3bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:registered-filled" /></template>
