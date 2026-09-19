<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfkqo-b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dfkqo-b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:megaphone-20-solid" /></template>
