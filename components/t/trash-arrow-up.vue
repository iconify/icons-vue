<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmaeok76a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmaeok76a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:trash-arrow-up" /></template>
