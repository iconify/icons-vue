<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bun7qr1sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bun7qr1sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:signal" /></template>
