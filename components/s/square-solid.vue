<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2-7v0z6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2-7v0z6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-solid" /></template>
