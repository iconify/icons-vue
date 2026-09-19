<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oprlnbclx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oprlnbclx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:yelp" /></template>
