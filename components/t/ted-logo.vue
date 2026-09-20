<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj6icb6in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj6icb6in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ted-logo" /></template>
