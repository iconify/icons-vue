<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqd-mv85n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqd-mv85n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:playerdotme" /></template>
