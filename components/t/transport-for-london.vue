<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o577myblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o577myblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:transport-for-london" /></template>
