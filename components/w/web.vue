<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnv2_3btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":707};
const content = `<path class="bnv2_3btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:web" /></template>
