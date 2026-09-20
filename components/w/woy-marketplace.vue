<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9snh7bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k9snh7bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:woy-marketplace" /></template>
