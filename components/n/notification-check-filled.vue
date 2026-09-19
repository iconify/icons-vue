<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tidwzyb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tidwzyb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-check-filled" /></template>
