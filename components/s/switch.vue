<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwxg69k_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zwxg69k_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:switch" /></template>
