<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ectymnybn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ectymnybn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-basket-remove-remix" /></template>
