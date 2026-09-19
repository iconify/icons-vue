<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_l042kxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e_l042kxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:qr-code" /></template>
