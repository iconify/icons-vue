<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7wg_lntv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o7wg_lntv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ubuntu-wordmark" /></template>
