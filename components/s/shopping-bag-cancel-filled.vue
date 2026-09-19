<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc1rkybia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc1rkybia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-bag-cancel-filled" /></template>
