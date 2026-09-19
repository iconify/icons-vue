<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cedp-nw9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cedp-nw9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:triangle-down-filled" /></template>
