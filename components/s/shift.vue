<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efnp5n2eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="efnp5n2eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:shift" /></template>
