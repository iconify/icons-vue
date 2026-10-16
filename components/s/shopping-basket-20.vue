<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_cl9xend.css';
import '../../css/t/toul2psij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v_cl9xend"/><path class="toul2psij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shopping-basket-20" /></template>
