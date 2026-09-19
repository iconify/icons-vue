<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v524kibsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v524kibsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:spotify-filled" /></template>
