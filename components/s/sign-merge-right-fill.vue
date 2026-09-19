<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg8v_ccue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vg8v_ccue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-merge-right-fill" /></template>
