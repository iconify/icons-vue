<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7unewr-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7unewr-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:tv" /></template>
