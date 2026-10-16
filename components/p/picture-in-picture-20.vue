<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co0vf9bvy.css';
import '../../css/c/cukx4cbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="cukx4cbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picture-in-picture-20" /></template>
