<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gitrsibxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gitrsibxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mouse-wireless-1-remix" /></template>
