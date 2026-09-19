<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmytx5v5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="kmytx5v5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tty" /></template>
