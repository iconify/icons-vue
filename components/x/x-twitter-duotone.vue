<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9jm7-0vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9jm7-0vp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:x-twitter-duotone" /></template>
