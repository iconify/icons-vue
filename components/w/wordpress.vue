<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj9wosb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj9wosb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wordpress" /></template>
