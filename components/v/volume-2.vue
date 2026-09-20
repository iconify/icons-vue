<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twoxdzb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="twoxdzb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:volume-2" /></template>
