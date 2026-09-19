<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svgy8st2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="svgy8st2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wireless-small" /></template>
