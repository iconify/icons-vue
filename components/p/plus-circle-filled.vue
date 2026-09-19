<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu845wn3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu845wn3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:plus-circle-filled" /></template>
