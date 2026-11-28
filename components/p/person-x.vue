<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlts9hb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlts9hb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:person-x" /></template>
