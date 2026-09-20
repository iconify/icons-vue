<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sixwq45kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sixwq45kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-bag-2-line" /></template>
