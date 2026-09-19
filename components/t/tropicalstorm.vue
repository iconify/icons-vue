<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9o3dobzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v9o3dobzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tropicalstorm" /></template>
