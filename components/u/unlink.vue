<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0dhspbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":18};
const content = `<path class="h0dhspbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:unlink" /></template>
