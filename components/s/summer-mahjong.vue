<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6lq4q6dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="o6lq4q6dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:summer-mahjong" /></template>
