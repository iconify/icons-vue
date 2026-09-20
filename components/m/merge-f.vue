<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3hoj7_rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="s3hoj7_rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:merge-f" /></template>
