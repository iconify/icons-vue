<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmn6akbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zmn6akbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-check-20-solid" /></template>
