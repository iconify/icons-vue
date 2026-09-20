<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0i15fbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k0i15fbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:window-restore" /></template>
