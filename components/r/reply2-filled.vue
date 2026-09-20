<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c77347-xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c77347-xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:reply2-filled" /></template>
