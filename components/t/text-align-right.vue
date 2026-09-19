<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyv40dbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lyv40dbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:text-align-right" /></template>
