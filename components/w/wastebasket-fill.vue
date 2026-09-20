<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swqj4kzfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swqj4kzfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wastebasket-fill" /></template>
