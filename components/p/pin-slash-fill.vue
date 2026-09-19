<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5wjhcbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="e5wjhcbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pin-slash-fill" /></template>
