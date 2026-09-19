<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c29fr0bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c29fr0bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-then-curving-down-arrow" /></template>
