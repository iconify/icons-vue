<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhc-4dsnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jhc-4dsnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:money-bag-small" /></template>
