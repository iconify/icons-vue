<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8_ggj7jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8_ggj7jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sage" /></template>
