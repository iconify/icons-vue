<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtnq_1kzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wtnq_1kzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-subtract-solid" /></template>
