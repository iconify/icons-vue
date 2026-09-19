<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyzjse4-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyzjse4-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:skip-next" /></template>
