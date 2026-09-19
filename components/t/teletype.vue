<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s759206rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s759206rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:teletype" /></template>
