<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq24u9byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eq24u9byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wheelchair-remix" /></template>
