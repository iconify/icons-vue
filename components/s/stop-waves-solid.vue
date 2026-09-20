<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-lo7wsxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-lo7wsxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop-waves-solid" /></template>
