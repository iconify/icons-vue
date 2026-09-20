<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djsqtnb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="djsqtnb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:modulz-logo" /></template>
