<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4skdrktw.css';
import '../../css/t/tioi38l2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4skdrktw"/><path class="tioi38l2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-5-fill" /></template>
