<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkr0cdc7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkr0cdc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text" /></template>
