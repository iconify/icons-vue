<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec-0r3lvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec-0r3lvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-2000-light" /></template>
