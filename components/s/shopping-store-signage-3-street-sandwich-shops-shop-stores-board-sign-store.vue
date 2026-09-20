<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdj9-9bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gdj9-9bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-store-signage-3-street-sandwich-shops-shop-stores-board-sign-store" /></template>
