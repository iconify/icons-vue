<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2g5uz83b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2g5uz83b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stretching" /></template>
