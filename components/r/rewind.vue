<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii4luiqss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ii4luiqss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rewind" /></template>
