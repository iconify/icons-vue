<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acc2ezl_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="acc2ezl_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag" /></template>
