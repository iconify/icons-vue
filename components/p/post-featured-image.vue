<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmsnur0zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="pmsnur0zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-featured-image" /></template>
