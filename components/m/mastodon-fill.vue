<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-8an5zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-8an5zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mastodon-fill" /></template>
