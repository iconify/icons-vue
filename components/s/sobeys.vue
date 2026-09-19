<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujxxnx5nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujxxnx5nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sobeys" /></template>
