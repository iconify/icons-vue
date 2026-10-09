<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a29x5nygp.css';
import '../../css/y/yq9xkk4gp.css';
import '../../css/s/sd5zehitt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a29x5nygp"/><path class="yq9xkk4gp"/><path class="sd5zehitt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-sock-20-bold" /></template>
