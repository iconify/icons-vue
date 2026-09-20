<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjx4ulw2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jjx4ulw2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rand-outline" /></template>
