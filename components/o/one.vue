<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kemnvdb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kemnvdb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:one" /></template>
