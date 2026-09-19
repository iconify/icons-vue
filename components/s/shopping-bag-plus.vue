<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar8e79b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar8e79b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-bag-plus" /></template>
