<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au00-4bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au00-4bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:metager" /></template>
