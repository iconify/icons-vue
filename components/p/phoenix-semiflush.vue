<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7zxc20fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7zxc20fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:phoenix-semiflush" /></template>
