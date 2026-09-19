<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shjrjgzhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="shjrjgzhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-then-curving-up-arrow" /></template>
