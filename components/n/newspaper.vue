<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw8kuhb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8kuhb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:newspaper" /></template>
