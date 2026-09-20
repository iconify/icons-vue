<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs6xi3b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs6xi3b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:subtract" /></template>
