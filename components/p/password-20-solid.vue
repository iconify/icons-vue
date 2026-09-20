<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-k1v4bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e-k1v4bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-20-solid" /></template>
