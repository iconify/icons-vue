<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yelp_8bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yelp_8bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:rocket-fill" /></template>
