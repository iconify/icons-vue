<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzh7s7btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jzh7s7btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:yen-solid" /></template>
