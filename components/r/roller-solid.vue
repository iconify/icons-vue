<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz9kdgpzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kz9kdgpzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:roller-solid" /></template>
