<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3qhzejxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3qhzejxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:mask-20-solid" /></template>
