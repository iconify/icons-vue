<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab-pd873z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab-pd873z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:yelp-fill" /></template>
