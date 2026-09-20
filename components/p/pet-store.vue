<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljv9kz7ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ljv9kz7ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pet-store" /></template>
