<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak9rbxbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak9rbxbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-bag-2-fill" /></template>
