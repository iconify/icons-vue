<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5b5ebbiz.css';
import '../../css/z/zrqjhsbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f5b5ebbiz"/><path class="zrqjhsbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-catergories-dress-clothing-dress-skirt-women" /></template>
