<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu7shmw8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path clip-rule="evenodd" class="cu7shmw8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-google-plus" /></template>
