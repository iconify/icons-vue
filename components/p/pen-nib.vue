<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt2o9cczv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt2o9cczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pen-nib" /></template>
