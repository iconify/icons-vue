<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb-a7db1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nb-a7db1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:rafting" /></template>
