<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgg4dq8pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tgg4dq8pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users-nearby" /></template>
