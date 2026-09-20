<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf-rf75mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf-rf75mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sepa" /></template>
