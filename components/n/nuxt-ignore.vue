<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv1hz3b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bv1hz3b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nuxt-ignore" /></template>
