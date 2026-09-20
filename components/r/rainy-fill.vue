<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd54be7bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd54be7bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rainy-fill" /></template>
