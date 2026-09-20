<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfn4ue8nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfn4ue8nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:share-off" /></template>
