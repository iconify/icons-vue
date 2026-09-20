<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3rsk1bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3rsk1bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:shopping-basket" /></template>
