<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd2ok_1gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd2ok_1gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-outline" /></template>
