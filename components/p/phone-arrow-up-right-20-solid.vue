<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0dm81bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p0dm81bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:phone-arrow-up-right-20-solid" /></template>
