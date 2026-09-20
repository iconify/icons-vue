<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfy2zropo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pfy2zropo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:table-tennis" /></template>
