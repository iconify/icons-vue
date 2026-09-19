<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o17yqtb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o17yqtb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:pear" /></template>
