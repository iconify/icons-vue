<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_0z8-bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w_0z8-bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:t-rex-small-filled" /></template>
