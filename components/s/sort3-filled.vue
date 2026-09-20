<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyweekm0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyweekm0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort3-filled" /></template>
