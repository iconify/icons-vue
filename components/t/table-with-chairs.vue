<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnp3iub6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bnp3iub6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:table-with-chairs" /></template>
