<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0n3v1bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z0n3v1bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:suitcase-under-list-beside-checkmark" /></template>
