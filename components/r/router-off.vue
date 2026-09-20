<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3uyy0blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3uyy0blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:router-off" /></template>
