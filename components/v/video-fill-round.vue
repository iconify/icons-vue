<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvv0n5b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvv0n5b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-fill-round" /></template>
