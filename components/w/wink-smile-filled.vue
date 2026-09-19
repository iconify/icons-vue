<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxsj9xn3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxsj9xn3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wink-smile-filled" /></template>
