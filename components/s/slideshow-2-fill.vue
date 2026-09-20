<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj5ckp7co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj5ckp7co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slideshow-2-fill" /></template>
