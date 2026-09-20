<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzku4xb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzku4xb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:umbrella-closed" /></template>
