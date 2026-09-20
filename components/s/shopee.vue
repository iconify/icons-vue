<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5snt8_wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5snt8_wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:shopee" /></template>
