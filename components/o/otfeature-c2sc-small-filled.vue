<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quhe-fjie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="quhe-fjie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-c2sc-small-filled" /></template>
