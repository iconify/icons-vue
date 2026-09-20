<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1yk2dbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1yk2dbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:watch2" /></template>
