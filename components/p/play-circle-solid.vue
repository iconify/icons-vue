<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp0wu5zpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp0wu5zpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:play-circle-solid" /></template>
