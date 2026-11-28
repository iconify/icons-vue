<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-ublab8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ublab8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:palette-edit" /></template>
