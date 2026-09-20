<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iimb0g9ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iimb0g9ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sitting-tank-toilet-and-droplet" /></template>
