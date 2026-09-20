<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0jgelb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="e0jgelb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shield-x-solid" /></template>
