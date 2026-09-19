<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj0yd0xaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj0yd0xaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:phone-missed-call" /></template>
