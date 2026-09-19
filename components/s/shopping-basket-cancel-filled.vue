<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sowc0zb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sowc0zb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-basket-cancel-filled" /></template>
