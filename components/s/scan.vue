<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnhhb7bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnhhb7bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scan" /></template>
