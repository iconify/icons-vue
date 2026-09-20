<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1lv9tb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="b1lv9tb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:parking-11" /></template>
