<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shkk78fvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shkk78fvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:work-from-home-user-pet-cat" /></template>
