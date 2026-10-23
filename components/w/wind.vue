<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilhl5o__u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilhl5o__u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wind" /></template>
