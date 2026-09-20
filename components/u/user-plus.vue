<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjorfy6hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjorfy6hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-plus" /></template>
