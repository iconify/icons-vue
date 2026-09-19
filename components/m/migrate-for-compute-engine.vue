<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vatk52b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vatk52b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:migrate-for-compute-engine" /></template>
