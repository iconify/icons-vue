<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf94p7bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf94p7bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shaka-02" /></template>
