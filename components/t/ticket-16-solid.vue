<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb12aeggk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nb12aeggk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ticket-16-solid" /></template>
