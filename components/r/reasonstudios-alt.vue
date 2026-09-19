<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebr0d7qtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebr0d7qtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:reasonstudios-alt" /></template>
