<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxkvu5bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxkvu5bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:signal-solid" /></template>
