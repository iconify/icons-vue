<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu7vai-4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu7vai-4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ship-x" /></template>
