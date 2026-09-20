<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aawv7kwfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aawv7kwfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:openai" /></template>
