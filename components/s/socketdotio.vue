<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atgcdcbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atgcdcbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:socketdotio" /></template>
