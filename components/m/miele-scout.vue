<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scsc91bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scsc91bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:miele-scout" /></template>
