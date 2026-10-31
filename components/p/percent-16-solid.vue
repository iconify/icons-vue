<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq5df5bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fq5df5bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:percent-16-solid" /></template>
