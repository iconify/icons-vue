<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz-9f21ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bz-9f21ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-then-curving-up-arrow-filled" /></template>
