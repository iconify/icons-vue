<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leqet9sky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="leqet9sky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:warn-triangle-filled" /></template>
