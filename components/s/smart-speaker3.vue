<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmqw1zl_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmqw1zl_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-speaker3" /></template>
