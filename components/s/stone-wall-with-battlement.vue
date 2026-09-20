<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g04p4hb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g04p4hb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-wall-with-battlement" /></template>
