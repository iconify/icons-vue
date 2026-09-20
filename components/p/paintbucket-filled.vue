<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npf7jgx5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npf7jgx5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paintbucket-filled" /></template>
