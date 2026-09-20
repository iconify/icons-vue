<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr2wve6of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr2wve6of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:uv-index" /></template>
