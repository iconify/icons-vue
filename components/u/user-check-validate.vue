<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk-trub3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pk-trub3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-check-validate" /></template>
