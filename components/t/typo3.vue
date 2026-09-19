<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh0qghayh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="lh0qghayh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:typo3" /></template>
