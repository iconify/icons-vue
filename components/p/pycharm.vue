<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz0s3k_1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yz0s3k_1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pycharm" /></template>
