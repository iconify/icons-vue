<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xugmi0cit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xugmi0cit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:star-fill" /></template>
