<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq8b3yb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kq8b3yb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wifi-20-solid" /></template>
