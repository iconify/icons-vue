<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4qth8mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt4qth8mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-bag-minus-filled" /></template>
