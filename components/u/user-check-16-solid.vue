<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-5g-4kxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-5g-4kxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-check-16-solid" /></template>
